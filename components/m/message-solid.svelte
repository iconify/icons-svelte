<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a5ra0hmjp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a5ra0hmjp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:message-solid" {...props}></Icon>
