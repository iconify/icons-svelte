<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s3q8ujb9s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s3q8ujb9s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:biceps-flexed" {...props}></Icon>
