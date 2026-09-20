<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qf3xb6b8z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qf3xb6b8z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:dfir-iris-dark" {...props}></Icon>
