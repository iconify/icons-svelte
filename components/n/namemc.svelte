<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m_q1hyb6d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m_q1hyb6d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:namemc" {...props}></Icon>
