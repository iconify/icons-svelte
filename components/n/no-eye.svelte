<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uuznmyb7t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":528,"height":480};
const content = `<path class="uuznmyb7t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:no-eye" {...props}></Icon>
