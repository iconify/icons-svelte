<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/az4cwab1h.css';
import '../../css/o/ouobwmwuo.css';
import '../../css/b/b4ddgubbd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="az4cwab1h"/><path class="ouobwmwuo"/><path class="b4ddgubbd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:battery-full-20" {...props}></Icon>
