<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u_byhbb7v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="u_byhbb7v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:arrow-left-circle-solid" {...props}></Icon>
