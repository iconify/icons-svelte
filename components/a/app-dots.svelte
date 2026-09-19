<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fmkfoccpl.css';
import '../../css/w/wllfbt0-k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="duoicon-primary-layer fmkfoccpl"/><path class="duoicon-secondary-layer wllfbt0-k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="duo-icons:app-dots" {...props}></Icon>
