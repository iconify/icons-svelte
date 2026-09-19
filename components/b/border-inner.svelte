<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iy91t1bnu.css';
import '../../css/n/nas02gbsv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iy91t1bnu"/><path class="nas02gbsv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:border-inner" {...props}></Icon>
