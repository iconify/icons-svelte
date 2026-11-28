<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n-9m0zvwp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n-9m0zvwp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:folder-alert" {...props}></Icon>
