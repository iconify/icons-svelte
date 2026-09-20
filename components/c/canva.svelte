<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/so8rqccvs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="so8rqccvs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:canva" {...props}></Icon>
