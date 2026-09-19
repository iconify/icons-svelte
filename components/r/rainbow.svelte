<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ootoywbra.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":33,"height":24};
const content = `<path class="ootoywbra"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:rainbow" {...props}></Icon>
