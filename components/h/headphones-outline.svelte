<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wpj0hbcby.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="wpj0hbcby"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:headphones-outline" {...props}></Icon>
