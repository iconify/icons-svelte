<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m_jrh9c3a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="m_jrh9c3a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:1-circle-fill" {...props}></Icon>
