<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ovnuc44id.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ovnuc44id"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:jenkins" {...props}></Icon>
