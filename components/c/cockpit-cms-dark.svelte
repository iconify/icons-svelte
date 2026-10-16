<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sffhwnb-a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":310,"height":310};
const content = `<path class="sffhwnb-a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:cockpit-cms-dark" {...props}></Icon>
