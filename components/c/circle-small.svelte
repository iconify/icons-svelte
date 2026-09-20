<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kdme6km3m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<circle class="kdme6km3m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:circle-small" {...props}></Icon>
