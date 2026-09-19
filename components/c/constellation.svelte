<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vo25m_tbu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vo25m_tbu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:constellation" {...props}></Icon>
