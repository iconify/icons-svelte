<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/niu_geqxg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="niu_geqxg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:badge-alert" {...props}></Icon>
