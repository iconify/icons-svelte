<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jwaqp4bcv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jwaqp4bcv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="feather:alert-octagon" {...props}></Icon>
