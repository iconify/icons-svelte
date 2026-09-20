<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u2m_kp2fl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u2m_kp2fl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:hand-pointer-sharp" {...props}></Icon>
