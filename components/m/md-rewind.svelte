<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/omh4idx2l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="omh4idx2l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:md-rewind" {...props}></Icon>
