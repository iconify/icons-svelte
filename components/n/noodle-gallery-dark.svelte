<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g3nqpne1g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="g3nqpne1g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:noodle-gallery-dark" {...props}></Icon>
