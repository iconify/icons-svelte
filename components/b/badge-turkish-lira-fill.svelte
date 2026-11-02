<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v7eq4abnd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v7eq4abnd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:badge-turkish-lira-fill" {...props}></Icon>
