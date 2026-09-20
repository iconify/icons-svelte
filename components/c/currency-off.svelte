<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q9jni4bio.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q9jni4bio"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:currency-off" {...props}></Icon>
