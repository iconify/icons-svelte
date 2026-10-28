<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hix4dmajl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hix4dmajl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:arrow-left-to-line" {...props}></Icon>
