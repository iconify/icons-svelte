<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gs8f3nbkm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gs8f3nbkm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:number-58-small" {...props}></Icon>
