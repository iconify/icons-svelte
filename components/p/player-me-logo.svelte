<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z6067ebcg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z6067ebcg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:player-me-logo" {...props}></Icon>
