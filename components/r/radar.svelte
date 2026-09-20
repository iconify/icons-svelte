<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrj6p8qat.css';
import '../../css/h/hlnn9u8yp.css';
import '../../css/h/hm7acebzo.css';
import '../../css/h/h_tsn8bxt.css';
import '../../css/a/aoc4qh-uh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="hlnn9u8yp"/><path class="hm7acebzo"/><circle class="h_tsn8bxt"/><path class="aoc4qh-uh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:radar" {...props}></Icon>
