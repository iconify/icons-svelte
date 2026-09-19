<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q-s3mkbpo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="q-s3mkbpo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dashicons:format-quote" {...props}></Icon>
