<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/st-5kubif.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="st-5kubif"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:arrow-split-right-alt" {...props}></Icon>
