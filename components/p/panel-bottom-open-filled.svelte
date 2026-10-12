<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hx7ywibap.css';
import '../../css/y/y4--wuesr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hx7ywibap"/><path clip-rule="evenodd" class="y4--wuesr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:panel-bottom-open-filled" {...props}></Icon>
