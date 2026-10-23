<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nk0nq-frr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nk0nq-frr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:cloud-moon" {...props}></Icon>
