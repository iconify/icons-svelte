<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b6b6vpb5x.css';
import '../../css/u/uu-fcqbzw.css';
import '../../css/x/xztz0wb3p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="b6b6vpb5x"/><path class="uu-fcqbzw"/><path class="xztz0wb3p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:pastefy-light" {...props}></Icon>
