<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yhdu9cbye.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="yhdu9cbye"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:baby-carriage" {...props}></Icon>
