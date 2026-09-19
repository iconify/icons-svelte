<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/na8gr4b-e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="na8gr4b-e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:game-die" {...props}></Icon>
