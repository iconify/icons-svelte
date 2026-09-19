<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gx7e5vbhr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gx7e5vbhr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:ikea-hektar3" {...props}></Icon>
