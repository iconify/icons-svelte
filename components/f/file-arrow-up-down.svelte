<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yyymuvb1x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yyymuvb1x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:file-arrow-up-down" {...props}></Icon>
