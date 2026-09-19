<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eb9f_wazq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eb9f_wazq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:grid-circle-plus" {...props}></Icon>
