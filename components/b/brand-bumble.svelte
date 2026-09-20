<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p_90l3b-v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p_90l3b-v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:brand-bumble" {...props}></Icon>
