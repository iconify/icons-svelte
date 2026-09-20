<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h03kt-8or.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h03kt-8or"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:heading-6" {...props}></Icon>
