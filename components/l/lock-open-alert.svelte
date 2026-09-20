<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o_hnx-b_p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o_hnx-b_p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:lock-open-alert" {...props}></Icon>
