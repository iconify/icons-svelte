<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g15gpjk6g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="g15gpjk6g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:person-snowshoeing" {...props}></Icon>
