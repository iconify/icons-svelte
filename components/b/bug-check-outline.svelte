<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xyes79och.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xyes79och"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:bug-check-outline" {...props}></Icon>
