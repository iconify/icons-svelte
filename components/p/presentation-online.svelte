<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/r/rxpkz-b5o.css';
import '../../css/i/il9-ih3wv.css';
import '../../css/f/fbvloacdy.css';
import '../../css/x/x5jv-2b5o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="rxpkz-b5o"/><path class="il9-ih3wv"/><path class="fbvloacdy"/><path class="x5jv-2b5o"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:presentation-online" {...props}></Icon>
