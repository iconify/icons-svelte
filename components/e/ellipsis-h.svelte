<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/okk6ekkxa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1408,"height":1280};
const content = `<path class="okk6ekkxa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:ellipsis-h" {...props}></Icon>
