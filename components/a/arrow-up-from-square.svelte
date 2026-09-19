<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g-3d572jk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="g-3d572jk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:arrow-up-from-square" {...props}></Icon>
