<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ucnu-4ubw.css';
import '../../css/n/ndqjaugsw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ucnu-4ubw"/><path class="ndqjaugsw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:panel-right-open-filled" {...props}></Icon>
