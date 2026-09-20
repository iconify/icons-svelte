<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eylj2m_hl.css';
import '../../css/i/i5ijq9zah.css';
import '../../css/e/e_xuapbsu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":65,"height":64};
const content = `<path class="eylj2m_hl"/><path class="i5ijq9zah"/><path class="e_xuapbsu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="medical-icon:i-health-education" {...props}></Icon>
