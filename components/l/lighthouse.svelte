<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/db-6pbbps.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="db-6pbbps"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:lighthouse" {...props}></Icon>
