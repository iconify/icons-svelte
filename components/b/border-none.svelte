<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vrq06_bxx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vrq06_bxx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi-light:border-none" {...props}></Icon>
