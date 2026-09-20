<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vfqal6bid.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vfqal6bid"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:dollar-fill" {...props}></Icon>
