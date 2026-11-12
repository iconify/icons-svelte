<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bnsz9xlwp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bnsz9xlwp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:cloud-flame" {...props}></Icon>
