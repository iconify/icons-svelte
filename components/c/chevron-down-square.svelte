<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pdzi00bpt.css';
import '../../css/h/hyrpu7bwm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pdzi00bpt"/><path class="hyrpu7bwm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:chevron-down-square" {...props}></Icon>
