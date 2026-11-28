<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iyzxg9-uh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="iyzxg9-uh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:monitor-slash-light" {...props}></Icon>
