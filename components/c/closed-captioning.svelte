<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pw6penbap.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="pw6penbap"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-regular:closed-captioning" {...props}></Icon>
