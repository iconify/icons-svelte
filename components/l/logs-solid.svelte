<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rxn8fwn7m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rxn8fwn7m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:logs-solid" {...props}></Icon>
