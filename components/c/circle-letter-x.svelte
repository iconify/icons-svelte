<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pqs_9jtvc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="pqs_9jtvc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:circle-letter-x" {...props}></Icon>
