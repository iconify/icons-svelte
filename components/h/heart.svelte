<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m_cc7qb8p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":1024};
const content = `<path class="m_cc7qb8p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:heart" {...props}></Icon>
