<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aqhi9hx0g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1185,"height":1000};
const content = `<path class="aqhi9hx0g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="websymbol:reply" {...props}></Icon>
