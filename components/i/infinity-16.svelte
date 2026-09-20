<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qr71j0btp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="qr71j0btp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:infinity-16" {...props}></Icon>
