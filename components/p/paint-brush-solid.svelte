<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/im8s7jxin.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="im8s7jxin"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:paint-brush-solid" {...props}></Icon>
