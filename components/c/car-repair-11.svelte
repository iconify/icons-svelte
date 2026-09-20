<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d6yzxzb0o.css';
import '../../css/k/kdqskdg1d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":11,"height":11};
const content = `<path class="d6yzxzb0o"/><path class="kdqskdg1d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:car-repair-11" {...props}></Icon>
