<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qix_boums.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qix_boums"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:lemon" {...props}></Icon>
