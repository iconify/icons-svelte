<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ohwqlgm2o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ohwqlgm2o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:bone-fractured-solid" {...props}></Icon>
