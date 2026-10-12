<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y53soubyt.css';
import '../../css/o/o604fd26w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y53soubyt"/><path class="o604fd26w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:house-plus-filled" {...props}></Icon>
