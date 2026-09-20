<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i2u1e0bhr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i2u1e0bhr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:polygon-pos" {...props}></Icon>
