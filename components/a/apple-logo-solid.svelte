<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v572r_bwi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="v572r_bwi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:apple-logo-solid" {...props}></Icon>
