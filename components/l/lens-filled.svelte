<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u3um9q0qi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="u3um9q0qi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:lens-filled" {...props}></Icon>
