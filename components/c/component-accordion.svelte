<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dgjw1g5ar.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dgjw1g5ar"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:component-accordion" {...props}></Icon>
