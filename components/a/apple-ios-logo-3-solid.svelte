<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a4zutr5jq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="a4zutr5jq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:apple-ios-logo-3-solid" {...props}></Icon>
