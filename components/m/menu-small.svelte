<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/blddsqbat.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="blddsqbat"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codex:menu-small" {...props}></Icon>
