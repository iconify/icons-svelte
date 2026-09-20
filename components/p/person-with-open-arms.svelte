<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k1q542b9z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="k1q542b9z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:person-with-open-arms" {...props}></Icon>
