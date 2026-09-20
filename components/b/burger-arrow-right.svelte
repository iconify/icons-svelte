<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nuqlkybfg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nuqlkybfg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:burger-arrow-right" {...props}></Icon>
