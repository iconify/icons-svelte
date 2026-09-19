<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/ph619sbso.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":444,"height":512};
const content = `<path class="ph619sbso"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:chartjs" {...props}></Icon>
