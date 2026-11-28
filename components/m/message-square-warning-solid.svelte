<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jh7_gacbi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jh7_gacbi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:message-square-warning-solid" {...props}></Icon>
