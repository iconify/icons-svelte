<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kiz36_bee.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="kiz36_bee"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:folder-keyhole" {...props}></Icon>
