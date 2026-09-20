<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dp71qgbag.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dp71qgbag"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:number-55-small" {...props}></Icon>
