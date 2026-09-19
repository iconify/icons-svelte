<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k9h1ahwix.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="k9h1ahwix"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:arrows-alt-h" {...props}></Icon>
