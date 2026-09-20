<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s1r71ybup.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="s1r71ybup"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="medical-icon:i-nutrition" {...props}></Icon>
