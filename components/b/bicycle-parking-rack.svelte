<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vh3ic1lnv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="vh3ic1lnv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:bicycle-parking-rack" {...props}></Icon>
