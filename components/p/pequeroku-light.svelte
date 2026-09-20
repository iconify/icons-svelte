<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l4fj0mnqe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="l4fj0mnqe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:pequeroku-light" {...props}></Icon>
