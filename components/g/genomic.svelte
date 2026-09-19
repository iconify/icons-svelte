<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/ze_c9dblz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ze_c9dblz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eos-icons:genomic" {...props}></Icon>
