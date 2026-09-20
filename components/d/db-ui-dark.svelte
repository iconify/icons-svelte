<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a98mh80fl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="a98mh80fl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:db-ui-dark" {...props}></Icon>
