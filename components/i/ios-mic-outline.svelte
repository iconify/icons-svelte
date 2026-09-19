<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s-e9bcc3c.css';
import '../../css/d/dr9-gqbcg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="s-e9bcc3c"/><path class="dr9-gqbcg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-mic-outline" {...props}></Icon>
