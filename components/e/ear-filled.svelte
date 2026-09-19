<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/beuj2j22z.css';
import '../../css/l/leb0srb7f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="beuj2j22z"/><path class="leb0srb7f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:ear-filled" {...props}></Icon>
