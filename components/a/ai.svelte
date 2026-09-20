<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zvhyx_bzt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zvhyx_bzt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:ai" {...props}></Icon>
