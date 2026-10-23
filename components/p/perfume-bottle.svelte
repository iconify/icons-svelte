<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pqefjjb3a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pqefjjb3a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:perfume-bottle" {...props}></Icon>
