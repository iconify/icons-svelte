<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eyqpfl7lx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eyqpfl7lx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:circle-stack" {...props}></Icon>
