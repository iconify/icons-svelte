<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v-k5ynfvo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1000,"height":1000};
const content = `<path class="v-k5ynfvo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="brandico:facebook-rect" {...props}></Icon>
