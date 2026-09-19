<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i7m_grmss.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="i7m_grmss"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:divide" {...props}></Icon>
