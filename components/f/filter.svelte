<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k1n9xp.css';
import '../../css/s/so-from-54.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k1n9xp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="line-md:filter" {...props}></Icon>
