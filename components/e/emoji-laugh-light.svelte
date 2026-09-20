<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qi4tymrtz.css';
import '../../css/n/n6czn--le.css';
import '../../css/f/fjvtlht_p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qi4tymrtz"/><path clip-rule="evenodd" class="n6czn--le"/><path clip-rule="evenodd" class="fjvtlht_p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:emoji-laugh-light" {...props}></Icon>
