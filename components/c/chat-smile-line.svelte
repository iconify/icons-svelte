<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eyr3-ccue.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eyr3-ccue"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:chat-smile-line" {...props}></Icon>
