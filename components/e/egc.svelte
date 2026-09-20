<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/znh1p3cxt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="znh1p3cxt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:egc" {...props}></Icon>
