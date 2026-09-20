<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qjys986ht.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qjys986ht"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:netapp" {...props}></Icon>
