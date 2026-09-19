<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ajsledcvw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":440,"height":384};
const content = `<path class="ajsledcvw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:flight-takeoff" {...props}></Icon>
