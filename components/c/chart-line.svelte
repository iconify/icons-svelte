<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bbbu5e-zd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bbbu5e-zd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:chart-line" {...props}></Icon>
