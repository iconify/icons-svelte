<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p_p-bomet.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="p_p-bomet"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:roadwork" {...props}></Icon>
