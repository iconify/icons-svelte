<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f664y_bpe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f664y_bpe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:chat-smile-2-fill" {...props}></Icon>
