<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sp0qxs3rm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="sp0qxs3rm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:add-square-fill" {...props}></Icon>
