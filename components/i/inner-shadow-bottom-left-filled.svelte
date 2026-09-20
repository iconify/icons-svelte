<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uo5_o1bts.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uo5_o1bts"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:inner-shadow-bottom-left-filled" {...props}></Icon>
