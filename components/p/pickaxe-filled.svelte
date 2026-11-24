<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/smr82qbco.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="smr82qbco"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:pickaxe-filled" {...props}></Icon>
