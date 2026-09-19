<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/du4h6ib8p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1025};
const content = `<path class="du4h6ib8p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:lasso" {...props}></Icon>
