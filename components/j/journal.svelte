<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oxzug7bsh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="oxzug7bsh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:journal" {...props}></Icon>
