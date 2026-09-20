<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qb6yg9b8f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qb6yg9b8f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:air-transat" {...props}></Icon>
