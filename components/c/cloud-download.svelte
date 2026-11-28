<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/no9jctb3y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="no9jctb3y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:cloud-download" {...props}></Icon>
