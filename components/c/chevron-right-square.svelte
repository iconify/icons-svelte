<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pdzi00bpt.css';
import '../../css/g/g39-95b8q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pdzi00bpt"/><path class="g39-95b8q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:chevron-right-square" {...props}></Icon>
