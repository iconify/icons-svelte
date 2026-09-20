<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e1bsn1l_c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e1bsn1l_c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:format-list-bulleted-type" {...props}></Icon>
