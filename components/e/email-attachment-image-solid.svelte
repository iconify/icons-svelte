<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o8ll5jb6j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="o8ll5jb6j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:email-attachment-image-solid" {...props}></Icon>
