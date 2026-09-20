<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mw50y7rwg.css';
import '../../css/e/ec0iwibgb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mw50y7rwg"/><path class="ec0iwibgb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:image-trash-light" {...props}></Icon>
