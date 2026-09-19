<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lkend5bbc.css';
import '../../css/o/o0czmk70w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="lkend5bbc"/><path class="o0czmk70w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:paintbucket" {...props}></Icon>
