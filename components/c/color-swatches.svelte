<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/k/kh6ar9beh.css';
import '../../css/x/xy86oib6j.css';
import '../../css/p/pgjz8fb7e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="kh6ar9beh"/><path class="xy86oib6j"/><path class="pgjz8fb7e"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:color-swatches" {...props}></Icon>
