<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qq7v8iwzd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1536,"height":1504};
const content = `<path class="qq7v8iwzd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:linkedin" {...props}></Icon>
