<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tt_t72bdg.css';
import '../../css/e/ej2tdcg6i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tt_t72bdg"/><path class="ej2tdcg6i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:armchair-filled" {...props}></Icon>
