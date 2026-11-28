<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/afxmlpbyf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="afxmlpbyf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:drill-check" {...props}></Icon>
