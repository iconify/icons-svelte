<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uzob4b76j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uzob4b76j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:led-strip-variant" {...props}></Icon>
