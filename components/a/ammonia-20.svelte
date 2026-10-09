<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gliza6bbj.css';
import '../../css/x/x8oc9s62k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="gliza6bbj"/><path class="x8oc9s62k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:ammonia-20" {...props}></Icon>
