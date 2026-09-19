<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m_19l7b3r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="m_19l7b3r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:person-arrow-up-from-line" {...props}></Icon>
