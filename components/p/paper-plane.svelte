<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aqy_veb6y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aqy_veb6y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="meteor-icons:paper-plane" {...props}></Icon>
