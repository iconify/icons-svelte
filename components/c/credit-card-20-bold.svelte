<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fwtvv7bpf.css';
import '../../css/s/sxyqv-bck.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="fwtvv7bpf"/><path class="sxyqv-bck"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:credit-card-20-bold" {...props}></Icon>
