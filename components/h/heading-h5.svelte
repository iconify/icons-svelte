<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fzvoi370p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fzvoi370p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gridicons:heading-h5" {...props}></Icon>
