<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d-xkbac8v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="d-xkbac8v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:align-h-center" {...props}></Icon>
