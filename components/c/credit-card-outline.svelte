<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w048f229i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="w048f229i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:credit-card-outline" {...props}></Icon>
