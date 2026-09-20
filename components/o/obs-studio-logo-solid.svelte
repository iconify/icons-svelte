<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n0q_up5ri.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="n0q_up5ri"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:obs-studio-logo-solid" {...props}></Icon>
