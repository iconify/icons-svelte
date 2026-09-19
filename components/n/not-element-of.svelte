<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ykos20fnv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ykos20fnv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:not-element-of" {...props}></Icon>
