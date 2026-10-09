<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m3xyfn7zl.css';
import '../../css/u/u9tjb0wcp.css';
import '../../css/n/ns0qimb2z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="m3xyfn7zl"/><path class="u9tjb0wcp"/><path class="ns0qimb2z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:co2-pipeline-48-bold" {...props}></Icon>
