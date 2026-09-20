<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/au0adx3wi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="au0adx3wi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:opensearch" {...props}></Icon>
