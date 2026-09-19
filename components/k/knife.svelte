<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kn84b3bex.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kn84b3bex"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:knife" {...props}></Icon>
