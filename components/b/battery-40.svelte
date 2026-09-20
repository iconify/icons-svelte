<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nbx4iobsw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nbx4iobsw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:battery-40" {...props}></Icon>
