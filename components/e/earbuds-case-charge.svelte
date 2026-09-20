<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nw569bbif.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nw569bbif"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:earbuds-case-charge" {...props}></Icon>
