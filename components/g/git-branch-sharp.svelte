<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bxc1hnbek.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bxc1hnbek"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:git-branch-sharp" {...props}></Icon>
