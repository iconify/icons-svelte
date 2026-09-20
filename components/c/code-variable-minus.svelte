<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vlsw8r0tr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vlsw8r0tr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:code-variable-minus" {...props}></Icon>
