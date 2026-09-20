<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gds_2f.css';
import '../../css/s/so-from-86.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gds_2f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="line-md:at" {...props}></Icon>
