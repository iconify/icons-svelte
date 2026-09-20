<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qwhtb-9yk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qwhtb-9yk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:redox" {...props}></Icon>
