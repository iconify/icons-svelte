<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ato9klb9g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ato9klb9g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:caravan-fill-round" {...props}></Icon>
