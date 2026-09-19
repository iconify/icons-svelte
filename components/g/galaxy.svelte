<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vbtjuszjt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":896};
const content = `<path class="vbtjuszjt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:galaxy" {...props}></Icon>
