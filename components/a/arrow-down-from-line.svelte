<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/he8o9-b7a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="he8o9-b7a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:arrow-down-from-line" {...props}></Icon>
