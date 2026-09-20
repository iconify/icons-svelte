<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lr3krrblo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lr3krrblo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:meh-closed-eye" {...props}></Icon>
