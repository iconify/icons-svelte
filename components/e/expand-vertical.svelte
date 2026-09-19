<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t257m_b5x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t257m_b5x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:expand-vertical" {...props}></Icon>
