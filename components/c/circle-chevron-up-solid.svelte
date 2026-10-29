<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xgjmi9bdt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xgjmi9bdt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:circle-chevron-up-solid" {...props}></Icon>
