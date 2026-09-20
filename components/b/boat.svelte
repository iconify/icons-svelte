<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kb46vdbeu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="kb46vdbeu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:boat" {...props}></Icon>
