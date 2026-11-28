<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zgq30ub0m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="primary zgq30ub0m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:regex-duotone" {...props}></Icon>
