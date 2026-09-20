<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vlrbr0wwr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vlrbr0wwr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:keyboard-f3" {...props}></Icon>
