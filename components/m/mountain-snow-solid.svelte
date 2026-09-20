<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k_-u3dbnb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k_-u3dbnb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:mountain-snow-solid" {...props}></Icon>
