<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/esama2bqx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="esama2bqx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:lock-16" {...props}></Icon>
