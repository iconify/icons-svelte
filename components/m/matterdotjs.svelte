<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ia1w134er.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ia1w134er"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:matterdotjs" {...props}></Icon>
