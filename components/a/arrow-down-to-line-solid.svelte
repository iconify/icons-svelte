<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dahe0tbeg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dahe0tbeg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:arrow-down-to-line-solid" {...props}></Icon>
