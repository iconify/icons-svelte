<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wan7vd7uu.css';
import '../../css/m/m_3bu7b7s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="wan7vd7uu"/><path class="m_3bu7b7s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:messages-48-bold" {...props}></Icon>
