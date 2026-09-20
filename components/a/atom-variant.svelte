<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nvux9ccjg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nvux9ccjg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:atom-variant" {...props}></Icon>
