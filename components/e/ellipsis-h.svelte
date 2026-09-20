<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q713wstdn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="q713wstdn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:ellipsis-h" {...props}></Icon>
