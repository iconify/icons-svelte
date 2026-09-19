<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qlll7jbyi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="qlll7jbyi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:layout-rows-3" {...props}></Icon>
