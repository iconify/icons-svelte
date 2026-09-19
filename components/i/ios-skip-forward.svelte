<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/igi_seb-i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="igi_seb-i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-skip-forward" {...props}></Icon>
