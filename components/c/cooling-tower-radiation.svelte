<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u85ln7bqz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="u85ln7bqz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:cooling-tower-radiation" {...props}></Icon>
