<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t0hk93biq.css';
import '../../css/u/ufxw6wkpy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="t0hk93biq"/><path class="ufxw6wkpy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:direction-ltr-20" {...props}></Icon>
