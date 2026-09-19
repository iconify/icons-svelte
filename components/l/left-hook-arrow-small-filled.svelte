<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o16ffbc_p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="o16ffbc_p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:left-hook-arrow-small-filled" {...props}></Icon>
