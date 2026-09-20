<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jo52jq6wq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jo52jq6wq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:google-near-by-logo-solid" {...props}></Icon>
