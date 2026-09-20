<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m_ph7yb3w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m_ph7yb3w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mi:export" {...props}></Icon>
