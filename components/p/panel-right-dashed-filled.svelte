<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jys00cbqx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jys00cbqx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:panel-right-dashed-filled" {...props}></Icon>
