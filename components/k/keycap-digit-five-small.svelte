<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aog-1ebri.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="aog-1ebri"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:keycap-digit-five-small" {...props}></Icon>
