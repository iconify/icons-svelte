<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kr5qu_bcy.css';
import '../../css/d/dnb3cibqn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kr5qu_bcy"/><path clip-rule="evenodd" class="dnb3cibqn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:playing-cards-filled" {...props}></Icon>
