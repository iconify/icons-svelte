<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/weiag3brm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="weiag3brm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:docker-logo" {...props}></Icon>
