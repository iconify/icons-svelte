<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nat0y94jm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nat0y94jm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:certificate-check" {...props}></Icon>
