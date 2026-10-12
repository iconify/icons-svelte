<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/exe5mchjt.css';
import '../../css/f/f4f8fe34r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="exe5mchjt"/><path class="f4f8fe34r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:database-arrow-down-filled" {...props}></Icon>
