<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t4o-mf99w.css';
import '../../css/c/cnzpvyp0b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t4o-mf99w"/><path clip-rule="evenodd" class="cnzpvyp0b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:recive-twice-square-outline" {...props}></Icon>
