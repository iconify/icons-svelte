<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o_aa1909b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o_aa1909b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:ram-line" {...props}></Icon>
