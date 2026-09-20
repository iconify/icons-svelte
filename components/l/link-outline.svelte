<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y2m_egr6x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y2m_egr6x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="typcn:link-outline" {...props}></Icon>
