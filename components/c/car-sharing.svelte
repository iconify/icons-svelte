<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hzgd0m_6f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="hzgd0m_6f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:car-sharing" {...props}></Icon>
