<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kr4mn3_sb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="kr4mn3_sb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:chat-heart" {...props}></Icon>
