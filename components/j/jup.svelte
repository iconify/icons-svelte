<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/irduc8btt.css';
import '../../css/z/z1s3debyr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="irduc8btt"/><path class="z1s3debyr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:jup" {...props}></Icon>
