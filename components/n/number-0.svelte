<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qbsqw0x7x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qbsqw0x7x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:number-0" {...props}></Icon>
