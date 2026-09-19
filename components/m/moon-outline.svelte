<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zh3rw9bca.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zh3rw9bca"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:moon-outline" {...props}></Icon>
