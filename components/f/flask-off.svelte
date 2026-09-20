<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/td2v5s9gv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="td2v5s9gv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:flask-off" {...props}></Icon>
