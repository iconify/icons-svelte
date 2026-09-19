<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h4qou-b1e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="h4qou-b1e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:face-robot" {...props}></Icon>
