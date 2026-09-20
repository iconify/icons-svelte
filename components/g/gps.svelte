<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/ml4nbmbrr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ml4nbmbrr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:gps" {...props}></Icon>
