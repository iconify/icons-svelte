<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z7d39lbsn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z7d39lbsn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="guidance:guest-within-height-limit-must-be-supervised" {...props}></Icon>
