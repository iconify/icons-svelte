<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qdo_ykkcl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qdo_ykkcl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:arrow-badge-right" {...props}></Icon>
