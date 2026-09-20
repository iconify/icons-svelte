<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o05-o4bbk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":25,"height":24};
const content = `<path class="o05-o4bbk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:layout-26" {...props}></Icon>
