<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/svjjnlb5d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="svjjnlb5d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:hanger2" {...props}></Icon>
