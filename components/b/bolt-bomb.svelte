<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a-sap6zpp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="a-sap6zpp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:bolt-bomb" {...props}></Icon>
