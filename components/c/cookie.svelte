<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lawee579x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="lawee579x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:cookie" {...props}></Icon>
