<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ush4msblo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ush4msblo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:picnic-site-15" {...props}></Icon>
