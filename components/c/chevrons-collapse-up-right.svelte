<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gicq85vhu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="gicq85vhu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:chevrons-collapse-up-right" {...props}></Icon>
