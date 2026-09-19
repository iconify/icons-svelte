<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g4a9t787l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="g4a9t787l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:hanger-one" {...props}></Icon>
