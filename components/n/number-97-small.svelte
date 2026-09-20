<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nhtex-0zk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nhtex-0zk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:number-97-small" {...props}></Icon>
