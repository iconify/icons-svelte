<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dxw2rj-de.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dxw2rj-de"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:database-search" {...props}></Icon>
