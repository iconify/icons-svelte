<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rmg3tqb7i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rmg3tqb7i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:netflix" {...props}></Icon>
