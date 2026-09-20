<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xwthxtbod.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xwthxtbod"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:mail-open" {...props}></Icon>
