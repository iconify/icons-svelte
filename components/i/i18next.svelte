<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/asu33ccus.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="asu33ccus"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:i18next" {...props}></Icon>
