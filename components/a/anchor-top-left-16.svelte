<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pltnho7ea.css';
import '../../css/v/voyj7e3gc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="pltnho7ea"/><path class="voyj7e3gc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:anchor-top-left-16" {...props}></Icon>
