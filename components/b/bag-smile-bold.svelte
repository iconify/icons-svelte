<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zst_8kb5f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zst_8kb5f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:bag-smile-bold" {...props}></Icon>
