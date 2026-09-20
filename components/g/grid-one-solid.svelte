<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d9z3f3bve.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d9z3f3bve"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:grid-one-solid" {...props}></Icon>
