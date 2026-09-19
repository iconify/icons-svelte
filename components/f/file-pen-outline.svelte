<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nf_q4tbwl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nf_q4tbwl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:file-pen-outline" {...props}></Icon>
