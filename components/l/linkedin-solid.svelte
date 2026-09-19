<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fxckmibkm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fxckmibkm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:linkedin-solid" {...props}></Icon>
