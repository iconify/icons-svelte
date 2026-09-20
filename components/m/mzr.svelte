<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zovxy3blb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zovxy3blb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:mzr" {...props}></Icon>
