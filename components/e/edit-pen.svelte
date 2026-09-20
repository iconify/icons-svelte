<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rebt0moqu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rebt0moqu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:edit-pen" {...props}></Icon>
