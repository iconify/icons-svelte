<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m_gvg0jpa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="m_gvg0jpa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:nec" {...props}></Icon>
