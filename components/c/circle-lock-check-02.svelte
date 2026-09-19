<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/w/wzzj1qb9b.css';
import '../../css/i/i3jt6ispm.css';
import '../../css/h/htizzhbzw.css';
import '../../css/n/nsynmcdef.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="wzzj1qb9b"/><path class="i3jt6ispm"/><circle class="htizzhbzw"/><path class="nsynmcdef"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:circle-lock-check-02" {...props}></Icon>
