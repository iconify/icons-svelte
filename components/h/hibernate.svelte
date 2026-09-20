<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f85_jjqda.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="f85_jjqda"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:hibernate" {...props}></Icon>
