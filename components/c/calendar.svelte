<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qrhh2bcxd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qrhh2bcxd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gridicons:calendar" {...props}></Icon>
