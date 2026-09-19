<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ify7xnn5j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="ify7xnn5j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:heart" {...props}></Icon>
