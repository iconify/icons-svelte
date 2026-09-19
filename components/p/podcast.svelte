<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jzwebw3gv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":24};
const content = `<path class="jzwebw3gv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:podcast" {...props}></Icon>
