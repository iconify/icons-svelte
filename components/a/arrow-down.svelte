<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m_ugq-blr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m_ugq-blr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="akar-icons:arrow-down" {...props}></Icon>
