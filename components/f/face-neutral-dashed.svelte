<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d6f7tdbut.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="d6f7tdbut"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:face-neutral-dashed" {...props}></Icon>
