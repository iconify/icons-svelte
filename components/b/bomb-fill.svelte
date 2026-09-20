<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s3mt6e6zb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s3mt6e6zb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:bomb-fill" {...props}></Icon>
