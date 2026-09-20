<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oryoyabvs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oryoyabvs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:card-text-outline" {...props}></Icon>
