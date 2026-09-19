<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eps3jxbis.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="eps3jxbis"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:dice-one" {...props}></Icon>
