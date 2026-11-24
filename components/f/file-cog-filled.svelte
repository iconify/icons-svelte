<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c4akmytgw.css';
import '../../css/u/uojfr4gpw.css';
import '../../css/r/rb_4au9oc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c4akmytgw"/><path clip-rule="evenodd" class="uojfr4gpw"/><path class="rb_4au9oc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:file-cog-filled" {...props}></Icon>
