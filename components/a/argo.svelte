<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aq8_dqbko.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aq8_dqbko"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:argo" {...props}></Icon>
