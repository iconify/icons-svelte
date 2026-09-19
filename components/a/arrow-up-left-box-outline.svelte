<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b_cj-5b1u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="b_cj-5b1u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:arrow-up-left-box-outline" {...props}></Icon>
