<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aals9abum.css';
import '../../css/m/mz-fxr5ss.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="aals9abum"/><path class="mz-fxr5ss"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:book-closed-stroke-20" {...props}></Icon>
