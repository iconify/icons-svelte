<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/slfr786iu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="slfr786iu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:environment" {...props}></Icon>
