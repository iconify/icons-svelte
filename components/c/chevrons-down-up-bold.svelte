<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a7-5n80rg.css';
import '../../css/l/leb-08bqy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a7-5n80rg"/><path class="leb-08bqy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:chevrons-down-up-bold" {...props}></Icon>
