<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/plk4vjb9x.css';
import '../../css/t/tl7q7ybjr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="plk4vjb9x"/><path class="tl7q7ybjr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:chef-hat-heart-bold" {...props}></Icon>
