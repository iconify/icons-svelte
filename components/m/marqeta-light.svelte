<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/im5fqoxyd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":553.4,"height":78.9};
const content = `<path class="im5fqoxyd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:marqeta-light" {...props}></Icon>
