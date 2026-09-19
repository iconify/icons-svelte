<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uglkwz-2l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":384};
const content = `<path class="uglkwz-2l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:accounts-add" {...props}></Icon>
