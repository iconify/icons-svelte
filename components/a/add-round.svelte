<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h2c6m_b_j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h2c6m_b_j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:add-round" {...props}></Icon>
