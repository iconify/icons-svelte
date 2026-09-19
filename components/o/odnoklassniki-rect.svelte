<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s6riy61-f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1000,"height":1000};
const content = `<path class="s6riy61-f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="websymbol:odnoklassniki-rect" {...props}></Icon>
