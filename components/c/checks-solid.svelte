<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cv48m6brz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cv48m6brz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:checks-solid" {...props}></Icon>
