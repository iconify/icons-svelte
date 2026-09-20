<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uk7og29zo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uk7og29zo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:folder-output-bold" {...props}></Icon>
