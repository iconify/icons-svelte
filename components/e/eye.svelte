<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k2bqgmpvm.css';
import '../../css/o/ove83va-t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":13};
const content = `<path class="k2bqgmpvm"/><path class="ove83va-t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="formkit:eye" {...props}></Icon>
