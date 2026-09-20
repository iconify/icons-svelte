<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q6o98sb4c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="q6o98sb4c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:chart" {...props}></Icon>
