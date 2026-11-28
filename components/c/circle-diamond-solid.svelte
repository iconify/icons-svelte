<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rmdz2cboc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rmdz2cboc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:circle-diamond-solid" {...props}></Icon>
