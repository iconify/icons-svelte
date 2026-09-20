<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x4ewktu2x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x4ewktu2x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:align-justify-fill" {...props}></Icon>
