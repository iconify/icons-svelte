<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aiki71mjc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="aiki71mjc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-brands:medrt" {...props}></Icon>
