<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fh_sowbzl.css';
import '../../css/x/xxr0bwmsb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fh_sowbzl"/><path class="xxr0bwmsb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:candy-line" {...props}></Icon>
