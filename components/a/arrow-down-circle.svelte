<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m_hp6klwa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="m_hp6klwa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-line-icons:arrow-down-circle" {...props}></Icon>
