<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nbs_ywbex.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nbs_ywbex"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:life-saver-outline" {...props}></Icon>
