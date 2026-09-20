<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tmrxj7bmv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tmrxj7bmv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:fugacloud" {...props}></Icon>
