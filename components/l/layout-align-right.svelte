<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k-k86xbqa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k-k86xbqa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:layout-align-right" {...props}></Icon>
