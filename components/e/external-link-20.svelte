<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tmi3g-t-d.css';
import '../../css/u/um9t76b7s.css';
import '../../css/c/cd_6icd4r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="tmi3g-t-d"/><path class="um9t76b7s"/><path class="cd_6icd4r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:external-link-20" {...props}></Icon>
