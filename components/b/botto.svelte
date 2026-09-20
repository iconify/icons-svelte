<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nx3i54y3i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nx3i54y3i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:botto" {...props}></Icon>
