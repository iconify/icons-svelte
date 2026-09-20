<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p_de7ibpo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p_de7ibpo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:curly-loop" {...props}></Icon>
