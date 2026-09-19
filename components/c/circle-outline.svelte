<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ehi9-muav.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":42,"height":42};
const content = `<path class="ehi9-muav"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="topcoat:circle-outline" {...props}></Icon>
