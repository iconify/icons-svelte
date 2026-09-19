<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ye52r9bed.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="ye52r9bed"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:house" {...props}></Icon>
