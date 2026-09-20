<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d3qec3ejp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="d3qec3ejp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:elastic-logo-solid" {...props}></Icon>
