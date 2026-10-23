<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b-l1cry_t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b-l1cry_t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="andrsrxn:menu-left" {...props}></Icon>
