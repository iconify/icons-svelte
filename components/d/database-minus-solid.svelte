<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xpmu4kbif.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xpmu4kbif"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:database-minus-solid" {...props}></Icon>
