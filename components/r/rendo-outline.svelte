<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/km3x3cedu.css';
import '../../css/c/c_pfbfb0h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="km3x3cedu"/><path clip-rule="evenodd" class="c_pfbfb0h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cuida:rendo-outline" {...props}></Icon>
