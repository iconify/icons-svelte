<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sht7gzb4f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sht7gzb4f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:layout-3-fill" {...props}></Icon>
