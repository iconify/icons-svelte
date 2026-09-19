<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lh7wvsr7y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="lh7wvsr7y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icons8:angle-up" {...props}></Icon>
