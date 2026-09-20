<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wy0uqnbmv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wy0uqnbmv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="prime:play" {...props}></Icon>
