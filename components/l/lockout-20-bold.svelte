<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/utjy8ob5b.css';
import '../../css/t/tzya4mwzm.css';
import '../../css/c/cofnes2hh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="utjy8ob5b"/><path class="tzya4mwzm"/><path class="cofnes2hh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:lockout-20-bold" {...props}></Icon>
