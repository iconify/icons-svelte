<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c5iqw1b3q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":667,"height":717};
const content = `<path class="c5iqw1b3q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:opera" {...props}></Icon>
