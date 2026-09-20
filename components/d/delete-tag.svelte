<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hr_w68m6s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="hr_w68m6s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:delete-tag" {...props}></Icon>
