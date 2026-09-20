<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ut7y1yr2k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ut7y1yr2k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:number-22-small" {...props}></Icon>
