<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xz-0psbpt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="xz-0psbpt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:person-crop-circle-badge-plus" {...props}></Icon>
