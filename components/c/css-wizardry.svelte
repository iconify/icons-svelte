<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eka3jccke.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eka3jccke"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:css-wizardry" {...props}></Icon>
