<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a7a2x58go.css';
import '../../css/j/jmmn-h0hh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a7a2x58go"/><path class="jmmn-h0hh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uim:clock-three" {...props}></Icon>
