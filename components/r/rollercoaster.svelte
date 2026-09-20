<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h23tj7btf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h23tj7btf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:rollercoaster" {...props}></Icon>
