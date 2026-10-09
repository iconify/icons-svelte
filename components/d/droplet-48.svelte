<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zqjtt0biw.css';
import '../../css/a/a3yyyw2au.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="zqjtt0biw"/><path class="a3yyyw2au"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:droplet-48" {...props}></Icon>
