<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sbh9kfbbm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sbh9kfbbm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:dice-2" {...props}></Icon>
