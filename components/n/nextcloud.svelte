<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u-c86pphd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u-c86pphd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:nextcloud" {...props}></Icon>
