<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/frgp4ccef.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="frgp4ccef"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:contacts-line" {...props}></Icon>
