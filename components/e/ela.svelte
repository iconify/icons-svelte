<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ojtwr_bkj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ojtwr_bkj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:ela" {...props}></Icon>
