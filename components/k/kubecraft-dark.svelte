<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xdagjjbbn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xdagjjbbn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:kubecraft-dark" {...props}></Icon>
