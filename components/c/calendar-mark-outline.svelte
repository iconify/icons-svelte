<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zydz8ub0o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zydz8ub0o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:calendar-mark-outline" {...props}></Icon>
