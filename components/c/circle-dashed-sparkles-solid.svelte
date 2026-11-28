<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kh_edkpcq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kh_edkpcq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:circle-dashed-sparkles-solid" {...props}></Icon>
