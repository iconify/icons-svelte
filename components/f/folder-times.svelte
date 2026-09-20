<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fn5z01lzv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fn5z01lzv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:folder-times" {...props}></Icon>
