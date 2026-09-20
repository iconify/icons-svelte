<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dd55jqb1l.css';
import '../../css/z/z7l2ccbgv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":40,"height":40};
const content = `<path class="dd55jqb1l"/><path class="z7l2ccbgv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iwwa:co2" {...props}></Icon>
