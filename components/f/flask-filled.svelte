<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xvtjgbmbw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="xvtjgbmbw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:flask-filled" {...props}></Icon>
