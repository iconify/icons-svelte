<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/ga6454bvx.css';
import '../../css/o/oj97bgbfh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ga6454bvx"/><path class="oj97bgbfh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:image-portrait" {...props}></Icon>
