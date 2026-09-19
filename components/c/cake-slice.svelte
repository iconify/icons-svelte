<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bv0rw9uug.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bv0rw9uug"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:cake-slice" {...props}></Icon>
