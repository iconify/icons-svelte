<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bp_dbydas.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bp_dbydas"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:award-fill" {...props}></Icon>
