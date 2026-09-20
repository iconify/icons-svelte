<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j7hs1xg-l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j7hs1xg-l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:material-design-icons" {...props}></Icon>
