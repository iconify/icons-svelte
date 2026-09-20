<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k1atvnm2b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k1atvnm2b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:inbox-plus-solid" {...props}></Icon>
