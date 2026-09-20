<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o-77kf30t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="o-77kf30t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:filedrop-dark" {...props}></Icon>
