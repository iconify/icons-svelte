<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zsg4_cbog.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zsg4_cbog"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:layout-content-bold" {...props}></Icon>
