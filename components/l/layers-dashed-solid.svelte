<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q_1ac_b9b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q_1ac_b9b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:layers-dashed-solid" {...props}></Icon>
