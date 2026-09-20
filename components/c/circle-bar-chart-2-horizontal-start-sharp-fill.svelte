<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wu97xdbpi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wu97xdbpi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:circle-bar-chart-2-horizontal-start-sharp-fill" {...props}></Icon>
