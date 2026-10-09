<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oh_lku0cz.css';
import '../../css/d/d7ym1acks.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="oh_lku0cz"/><path class="d7ym1acks"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:battery-module-20-bold" {...props}></Icon>
