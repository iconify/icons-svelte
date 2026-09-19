<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qzyiyj5jk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qzyiyj5jk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:folder-image-fill" {...props}></Icon>
