<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v5nclzbyk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v5nclzbyk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:file-zip-lock" {...props}></Icon>
