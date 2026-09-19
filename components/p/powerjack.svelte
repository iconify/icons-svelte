<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gpdcd9hma.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":960,"height":832};
const content = `<path class="gpdcd9hma"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:powerjack" {...props}></Icon>
