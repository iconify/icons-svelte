<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vm1p_cn4w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vm1p_cn4w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:iwiw-logo-2-block" {...props}></Icon>
