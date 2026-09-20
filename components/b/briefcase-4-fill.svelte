<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lf_t54b5f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lf_t54b5f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:briefcase-4-fill" {...props}></Icon>
