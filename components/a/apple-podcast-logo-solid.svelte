<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cqqqstb_q.css';
import '../../css/c/c3tksvemq.css';
import '../../css/m/mtikz3cki.css';
import '../../css/b/bepyfqbrc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cqqqstb_q"/><path clip-rule="evenodd" class="c3tksvemq"/><path clip-rule="evenodd" class="mtikz3cki"/><path class="bepyfqbrc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:apple-podcast-logo-solid" {...props}></Icon>
