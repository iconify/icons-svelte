<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aa74gusld.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="aa74gusld"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:mic-mv51" {...props}></Icon>
