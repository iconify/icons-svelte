<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oez_tozby.css';
import '../../css/y/y80r9ybqi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="oez_tozby"/><path class="y80r9ybqi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:crypto-encryption-key-bold" {...props}></Icon>
