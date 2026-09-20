<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/ddr_3pbvw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ddr_3pbvw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:align-justify-fill" {...props}></Icon>
