<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gqfws_12w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gqfws_12w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:monitor-fill" {...props}></Icon>
