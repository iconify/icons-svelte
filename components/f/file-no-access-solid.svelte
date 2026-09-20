<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g-e56suxy.css';
import '../../css/g/gjx1o8bfz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="g-e56suxy"/><path clip-rule="evenodd" class="gjx1o8bfz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:file-no-access-solid" {...props}></Icon>
