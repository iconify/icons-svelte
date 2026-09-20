<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h0sarzx0f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="h0sarzx0f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="medical-icon:i-restrooms" {...props}></Icon>
