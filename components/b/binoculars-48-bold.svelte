<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a1wytabzg.css';
import '../../css/n/n65fkti1c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="a1wytabzg"/><path class="n65fkti1c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:binoculars-48-bold" {...props}></Icon>
