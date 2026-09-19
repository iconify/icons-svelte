<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cf8ha8baf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cf8ha8baf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:hue-sync-strip" {...props}></Icon>
