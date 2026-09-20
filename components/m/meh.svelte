<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rnsy5qb4o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rnsy5qb4o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:meh" {...props}></Icon>
