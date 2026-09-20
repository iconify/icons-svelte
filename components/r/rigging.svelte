<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/owws5tblj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="owws5tblj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:rigging" {...props}></Icon>
