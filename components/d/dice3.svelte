<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kd61kebbw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="kd61kebbw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:dice3" {...props}></Icon>
