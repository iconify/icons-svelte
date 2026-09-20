<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n8famm2mn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="n8famm2mn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:key-opt-16" {...props}></Icon>
