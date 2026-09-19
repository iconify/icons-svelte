<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zgru5zbwe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zgru5zbwe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:leaf-alt-filled" {...props}></Icon>
