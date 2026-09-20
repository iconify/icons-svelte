<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lbskt6s3t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lbskt6s3t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:badge" {...props}></Icon>
