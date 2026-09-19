<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t36m_jbyh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t36m_jbyh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-outline:clipboard-check" {...props}></Icon>
