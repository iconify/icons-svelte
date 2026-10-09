<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y7575cbkw.css';
import '../../css/p/p769e2bzk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="y7575cbkw"/><path class="p769e2bzk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:drought-20" {...props}></Icon>
