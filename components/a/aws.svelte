<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hr-4_abky.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hr-4_abky"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:aws" {...props}></Icon>
