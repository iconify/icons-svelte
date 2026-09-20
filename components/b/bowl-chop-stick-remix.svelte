<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jk7cyca1a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="jk7cyca1a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:bowl-chop-stick-remix" {...props}></Icon>
