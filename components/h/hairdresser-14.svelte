<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ox5zndcug.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="ox5zndcug"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="osmic:hairdresser-14" {...props}></Icon>
