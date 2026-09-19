<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/msa_hlb-i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="msa_hlb-i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:panel-glassdoor-close" {...props}></Icon>
