<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i2y77wbtv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i2y77wbtv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:number-64-small" {...props}></Icon>
