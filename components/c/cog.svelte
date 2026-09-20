<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o12gpgb7i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="o12gpgb7i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:cog" {...props}></Icon>
