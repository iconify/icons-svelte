<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/evm6bqe-x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="evm6bqe-x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:newsblur-dark" {...props}></Icon>
