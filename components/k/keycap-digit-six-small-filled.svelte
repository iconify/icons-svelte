<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a08mf6bmv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="a08mf6bmv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:keycap-digit-six-small-filled" {...props}></Icon>
