<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/ja3ox0nfa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ja3ox0nfa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:contacts-book-upload-line" {...props}></Icon>
