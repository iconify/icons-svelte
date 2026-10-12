<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c7sy6m7uh.css';
import '../../css/t/tegin3b-f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="c7sy6m7uh"/><path class="tegin3b-f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:ear-off-filled" {...props}></Icon>
