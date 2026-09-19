<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dql26ryfr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dql26ryfr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:line-break" {...props}></Icon>
