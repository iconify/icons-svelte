<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x-jtknb6l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="x-jtknb6l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:hospital-fill" {...props}></Icon>
