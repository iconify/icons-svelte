<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w5ryw4bkw.css';
import '../../css/s/s8bjcqbop.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<circle class="w5ryw4bkw"/><path class="s8bjcqbop"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:fluxer" {...props}></Icon>
