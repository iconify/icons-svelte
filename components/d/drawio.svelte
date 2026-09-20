<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wkcbc4m_r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="wkcbc4m_r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:drawio" {...props}></Icon>
