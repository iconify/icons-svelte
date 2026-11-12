<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cxlf9wbrr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="cxlf9wbrr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:kwsx-radio-dark" {...props}></Icon>
