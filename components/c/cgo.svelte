<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/di6m5ibxb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="di6m5ibxb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:cgo" {...props}></Icon>
