<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g2t_7jw2w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="g2t_7jw2w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:down-outline" {...props}></Icon>
