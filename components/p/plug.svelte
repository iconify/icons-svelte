<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jid0abbpo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jid0abbpo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:plug" {...props}></Icon>
