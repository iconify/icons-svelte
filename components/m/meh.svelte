<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t2zc19bpz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":496,"height":512};
const content = `<path class="t2zc19bpz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-regular:meh" {...props}></Icon>
