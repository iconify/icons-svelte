<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aowlczbwh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="aowlczbwh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:apple-ios-logo-1-block" {...props}></Icon>
