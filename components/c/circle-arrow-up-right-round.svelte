<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k1i4gnl2c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k1i4gnl2c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:circle-arrow-up-right-round" {...props}></Icon>
