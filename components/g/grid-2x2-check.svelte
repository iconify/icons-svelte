<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ljh_osb8l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ljh_osb8l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:grid-2x2-check" {...props}></Icon>
