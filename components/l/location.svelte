<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/djm_3-bud.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="djm_3-bud"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pajamas:location" {...props}></Icon>
