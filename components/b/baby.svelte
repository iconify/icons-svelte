<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jhe3r6bqw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="jhe3r6bqw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:baby" {...props}></Icon>
