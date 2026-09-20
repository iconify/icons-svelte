<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ih-dr08ex.css';
import '../../css/n/ngqdbfb-g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ih-dr08ex"/><path class="ngqdbfb-g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:child" {...props}></Icon>
