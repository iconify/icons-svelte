<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qklwflbvp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qklwflbvp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:hermesseg-dark" {...props}></Icon>
