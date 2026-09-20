<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s85hp1bsm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s85hp1bsm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mi:fog" {...props}></Icon>
