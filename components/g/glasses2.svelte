<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zki3xmbyr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zki3xmbyr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:glasses2" {...props}></Icon>
