<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jrnzfppnd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jrnzfppnd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:abacus" {...props}></Icon>
