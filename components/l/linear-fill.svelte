<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oeg-uebww.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oeg-uebww"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:linear-fill" {...props}></Icon>
