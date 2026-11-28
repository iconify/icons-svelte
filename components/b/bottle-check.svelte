<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i2o7pfb5b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i2o7pfb5b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:bottle-check" {...props}></Icon>
