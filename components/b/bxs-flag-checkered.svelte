<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s3b4blbrq.css';
import '../../css/b/bo9dr7buy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s3b4blbrq"/><path class="bo9dr7buy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-flag-checkered" {...props}></Icon>
