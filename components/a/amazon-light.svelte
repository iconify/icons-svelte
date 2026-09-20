<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tb3lupxla.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="tb3lupxla"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:amazon-light" {...props}></Icon>
