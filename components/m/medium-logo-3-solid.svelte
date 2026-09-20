<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p65_h2bqg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="p65_h2bqg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:medium-logo-3-solid" {...props}></Icon>
