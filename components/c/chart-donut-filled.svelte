<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t7lwqcc9r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t7lwqcc9r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:chart-donut-filled" {...props}></Icon>
