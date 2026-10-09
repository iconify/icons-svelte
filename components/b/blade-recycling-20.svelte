<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lord7rwpc.css';
import '../../css/s/srp1dmbec.css';
import '../../css/n/nuv2zkaui.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="lord7rwpc"/><path class="srp1dmbec"/><path class="nuv2zkaui"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:blade-recycling-20" {...props}></Icon>
