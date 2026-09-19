<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cqn921buu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="cqn921buu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:phone-call-pause-fill-16" {...props}></Icon>
