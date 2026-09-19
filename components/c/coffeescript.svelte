<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qoo1b6bww.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="qoo1b6bww"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:coffeescript" {...props}></Icon>
