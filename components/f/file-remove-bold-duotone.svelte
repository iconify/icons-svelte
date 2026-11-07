<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kgd8bzbml.css';
import '../../css/q/qxh6zf45v.css';
import '../../css/b/bk9fnabkq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kgd8bzbml"/><path class="qxh6zf45v"/><path class="bk9fnabkq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:file-remove-bold-duotone" {...props}></Icon>
