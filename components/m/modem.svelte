<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yj9nae0yh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yj9nae0yh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uit:modem" {...props}></Icon>
