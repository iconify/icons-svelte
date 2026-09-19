<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/trwx034wa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":42,"height":42};
const content = `<path class="trwx034wa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="topcoat:behance" {...props}></Icon>
