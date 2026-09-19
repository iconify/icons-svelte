<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w-v9lvbyz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":563,"height":671};
const content = `<path class="w-v9lvbyz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:a" {...props}></Icon>
