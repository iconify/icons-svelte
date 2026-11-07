<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rzn135foz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rzn135foz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:bill-outline" {...props}></Icon>
