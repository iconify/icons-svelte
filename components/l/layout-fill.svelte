<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r01s9xbuq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r01s9xbuq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eva:layout-fill" {...props}></Icon>
