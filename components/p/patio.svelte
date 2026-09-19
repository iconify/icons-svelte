<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h43whc_ds.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h43whc_ds"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="guidance:patio" {...props}></Icon>
