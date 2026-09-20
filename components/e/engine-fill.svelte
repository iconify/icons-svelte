<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dtpw16buj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dtpw16buj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:engine-fill" {...props}></Icon>
