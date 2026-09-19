<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/euo4mnb-a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":451,"height":512};
const content = `<path class="euo4mnb-a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:nodemon" {...props}></Icon>
