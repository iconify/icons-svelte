<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n6ez4dboq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n6ez4dboq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:back" {...props}></Icon>
