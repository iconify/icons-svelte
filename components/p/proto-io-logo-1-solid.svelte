<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/opjh0-bau.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="opjh0-bau"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:proto-io-logo-1-solid" {...props}></Icon>
