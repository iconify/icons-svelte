<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z3a8ye1ad.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="z3a8ye1ad"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:esphome-light" {...props}></Icon>
