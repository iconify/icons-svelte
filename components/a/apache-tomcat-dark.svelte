<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yur3l-b2x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="yur3l-b2x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:apache-tomcat-dark" {...props}></Icon>
