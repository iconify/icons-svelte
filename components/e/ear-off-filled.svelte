<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f09f9qk1r.css';
import '../../css/t/tegin3b-f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="f09f9qk1r"/><path class="tegin3b-f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:ear-off-filled" {...props}></Icon>
