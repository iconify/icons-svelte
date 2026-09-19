<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/czux3lq-u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="czux3lq-u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ep:question-filled" {...props}></Icon>
