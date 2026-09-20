<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jqshe0eia.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jqshe0eia"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:keyboard-alt" {...props}></Icon>
