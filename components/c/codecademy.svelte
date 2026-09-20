<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ftp8ftbdh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ftp8ftbdh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:codecademy" {...props}></Icon>
