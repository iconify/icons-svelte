<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iv3t_9dyo.css';
import '../../css/h/h-fa8m_xj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iv3t_9dyo"/><path class="h-fa8m_xj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:cloud-arrow-up-light" {...props}></Icon>
