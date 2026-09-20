<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xm8lu6lmv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xm8lu6lmv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:database-import-outline" {...props}></Icon>
