<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rugf8t3bq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rugf8t3bq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxl:css3" {...props}></Icon>
