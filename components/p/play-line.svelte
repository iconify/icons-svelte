<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m_n8jw0cs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m_n8jw0cs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:play-line" {...props}></Icon>
