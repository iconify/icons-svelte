<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a0m25c.css';
import '../../css/z/zu019c.css';
import '../../css/z/zf6m_y.css';
import '../../css/r/rb0cwy.css';
import '../../css/s/so-from-10.css';
import '../../css/s/so-to-0.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a0m25c zu019c"/><path class="a0m25c zf6m_y"/><path class="a0m25c rb0cwy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="line-md:chevron-small-triple-right" {...props}></Icon>
