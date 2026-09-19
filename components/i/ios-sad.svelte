<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a3kl9nb6u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="a3kl9nb6u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-sad" {...props}></Icon>
