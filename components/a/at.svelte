<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pj2-m_bka.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pj2-m_bka"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="prime:at" {...props}></Icon>
