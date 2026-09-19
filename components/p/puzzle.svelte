<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ob_t6ubko.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="ob_t6ubko"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:puzzle" {...props}></Icon>
