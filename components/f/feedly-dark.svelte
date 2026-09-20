<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tf_3qnqnv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="tf_3qnqnv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:feedly-dark" {...props}></Icon>
