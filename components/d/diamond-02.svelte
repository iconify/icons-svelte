<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nowda5nca.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nowda5nca"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:diamond-02" {...props}></Icon>
