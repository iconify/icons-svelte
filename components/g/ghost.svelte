<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jul4siskq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="jul4siskq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:ghost" {...props}></Icon>
