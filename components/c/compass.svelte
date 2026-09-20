<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kzrfr_byi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kzrfr_byi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="typcn:compass" {...props}></Icon>
