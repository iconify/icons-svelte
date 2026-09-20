<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/ja69nhbvw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ja69nhbvw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:chat-remove-outline" {...props}></Icon>
