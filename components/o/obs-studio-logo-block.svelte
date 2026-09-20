<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k5s4bo5vb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="k5s4bo5vb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:obs-studio-logo-block" {...props}></Icon>
