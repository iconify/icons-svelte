<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c6w6e1bxz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c6w6e1bxz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:roller-shutter-switch" {...props}></Icon>
