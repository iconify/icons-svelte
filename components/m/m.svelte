<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b5hbqzbay.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":860,"height":654};
const content = `<path class="b5hbqzbay"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:m" {...props}></Icon>
