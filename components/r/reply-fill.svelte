<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h-ng6dyja.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="h-ng6dyja"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:reply-fill" {...props}></Icon>
