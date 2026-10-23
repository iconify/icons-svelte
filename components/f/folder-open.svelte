<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hv7h3ib2o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hv7h3ib2o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:folder-open" {...props}></Icon>
