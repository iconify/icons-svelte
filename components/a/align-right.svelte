<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wk-ngov9p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wk-ngov9p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:align-right" {...props}></Icon>
