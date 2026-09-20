<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ca3wkk41t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ca3wkk41t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:novita" {...props}></Icon>
