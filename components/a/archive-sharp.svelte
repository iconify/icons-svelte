<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ehuvywcsw.css';
import '../../css/k/k2om2cqop.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<rect class="ehuvywcsw"/><path class="k2om2cqop"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:archive-sharp" {...props}></Icon>
