<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/beqa1gb_p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="beqa1gb_p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:gif-outline" {...props}></Icon>
