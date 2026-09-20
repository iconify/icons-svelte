<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ycuch81po.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ycuch81po"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:filter-alt" {...props}></Icon>
