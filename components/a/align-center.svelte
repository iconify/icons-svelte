<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aqmg86b8p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="aqmg86b8p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zondicons:align-center" {...props}></Icon>
