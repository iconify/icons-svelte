<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oadu9_skn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oadu9_skn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:club" {...props}></Icon>
