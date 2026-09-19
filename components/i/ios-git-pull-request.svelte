<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l3on08bdw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="l3on08bdw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-git-pull-request" {...props}></Icon>
