<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pwtip4izv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pwtip4izv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:letter-m-circle-solid" {...props}></Icon>
