<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/og8okim2h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="og8okim2h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:apple-ios-logo-2-solid" {...props}></Icon>
