<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hwy0kfu6l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="hwy0kfu6l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="medical-icon:i-text-telephone" {...props}></Icon>
