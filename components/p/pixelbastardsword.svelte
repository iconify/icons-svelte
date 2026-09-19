<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c25m_hbpq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="c25m_hbpq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:pixelbastardsword" {...props}></Icon>
