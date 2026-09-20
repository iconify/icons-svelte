<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/haor4_unv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="haor4_unv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pajamas:flag" {...props}></Icon>
