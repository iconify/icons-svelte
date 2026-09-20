<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t5n2lnb_t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="t5n2lnb_t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:alt-arrow-right-outline" {...props}></Icon>
