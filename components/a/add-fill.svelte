<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gm63-8bxd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gm63-8bxd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:add-fill" {...props}></Icon>
