<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrj6p8qat.css';
import '../../css/o/oyj6fz_fl.css';
import '../../css/y/ytg_fz4um.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="oyj6fz_fl"/><path class="ytg_fz4um"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:house-arrow-left" {...props}></Icon>
