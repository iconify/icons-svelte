<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i58h6jb5t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i58h6jb5t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:folder-close-round" {...props}></Icon>
