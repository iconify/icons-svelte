<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fr-5ntbhr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fr-5ntbhr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:caret-right" {...props}></Icon>
