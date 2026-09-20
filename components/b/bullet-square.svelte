<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qcjf6bcsv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qcjf6bcsv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nrk:bullet-square" {...props}></Icon>
