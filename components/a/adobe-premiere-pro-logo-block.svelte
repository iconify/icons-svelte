<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k3kr0dbyr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="k3kr0dbyr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:adobe-premiere-pro-logo-block" {...props}></Icon>
