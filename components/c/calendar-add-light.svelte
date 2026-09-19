<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b8n1_cneq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b8n1_cneq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:calendar-add-light" {...props}></Icon>
