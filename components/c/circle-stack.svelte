<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/monbpoibt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="monbpoibt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-solid:circle-stack" {...props}></Icon>
