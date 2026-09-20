<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oody99b2i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oody99b2i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:maximize-circle-filled" {...props}></Icon>
