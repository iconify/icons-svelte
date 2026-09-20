<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vnetsu-me.css';
import '../../css/j/j7goiubdd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":576,"height":619};
const content = `<path class="vnetsu-me"/><path class="j7goiubdd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:orildo" {...props}></Icon>
