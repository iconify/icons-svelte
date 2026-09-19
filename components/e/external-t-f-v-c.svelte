<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wjwx6ab_w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="wjwx6ab_w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:external-t-f-v-c" {...props}></Icon>
