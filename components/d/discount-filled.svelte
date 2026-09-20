<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z8vaz6bvv.css';
import '../../css/p/pn6ejhb8x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z8vaz6bvv"/><path class="pn6ejhb8x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:discount-filled" {...props}></Icon>
