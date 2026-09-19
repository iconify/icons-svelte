<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jctvu8boi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="jctvu8boi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:dice-5" {...props}></Icon>
