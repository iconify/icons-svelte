<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/msn1kjbyk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="msn1kjbyk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:clipboard-check-filled" {...props}></Icon>
