<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k1cbjxi4x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":496,"height":512};
const content = `<path class="k1cbjxi4x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:laugh-wink" {...props}></Icon>
