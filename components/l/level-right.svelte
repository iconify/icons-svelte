<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v8o-nvzdw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="v8o-nvzdw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:level-right" {...props}></Icon>
