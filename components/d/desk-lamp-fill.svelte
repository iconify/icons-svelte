<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mk2wribdi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mk2wribdi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:desk-lamp-fill" {...props}></Icon>
