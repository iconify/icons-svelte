<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wzaf98bbw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wzaf98bbw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:alphabet-chinese" {...props}></Icon>
