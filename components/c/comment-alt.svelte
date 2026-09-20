<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nn_zwgrde.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="nn_zwgrde"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:comment-alt" {...props}></Icon>
