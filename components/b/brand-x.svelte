<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yh-qt9rta.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yh-qt9rta"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:brand-x" {...props}></Icon>
