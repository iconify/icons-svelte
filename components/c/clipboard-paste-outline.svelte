<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mxkbezb3a.css';
import '../../css/e/e3rn21oia.css';
import '../../css/w/w991tqbch.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mxkbezb3a"/><path class="e3rn21oia"/><path class="w991tqbch"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:clipboard-paste-outline" {...props}></Icon>
