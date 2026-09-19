<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j_1vvpbyl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j_1vvpbyl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:chat-circle-dots-filled" {...props}></Icon>
