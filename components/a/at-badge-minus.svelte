<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ussur-5ft.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="ussur-5ft"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:at-badge-minus" {...props}></Icon>
