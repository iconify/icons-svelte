<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrj6p8qat.css';
import '../../css/i/isv7l49qo.css';
import '../../css/v/va4yoc50j.css';
import '../../css/t/trsr16b4c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="isv7l49qo"/><ellipse class="va4yoc50j"/><path class="trsr16b4c"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:drum" {...props}></Icon>
