<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oxpe5mb8d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oxpe5mb8d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:navigation-code" {...props}></Icon>
