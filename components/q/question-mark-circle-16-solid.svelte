<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mqxitkbug.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="mqxitkbug"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:question-mark-circle-16-solid" {...props}></Icon>
