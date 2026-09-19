<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bv68dpb3m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="bv68dpb3m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:informationsource-small-filled" {...props}></Icon>
