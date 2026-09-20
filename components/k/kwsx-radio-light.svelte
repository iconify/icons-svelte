<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hh7x7d29g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hh7x7d29g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:kwsx-radio-light" {...props}></Icon>
