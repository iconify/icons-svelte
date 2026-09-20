<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ebzhk4bmm.css';
import '../../css/o/oufzmac7u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ebzhk4bmm"/><path clip-rule="evenodd" class="oufzmac7u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:ms-excel-solid" {...props}></Icon>
