<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k0tm76bpf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k0tm76bpf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:lira-circle-solid" {...props}></Icon>
