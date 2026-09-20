<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrj6p8qat.css';
import '../../css/p/poo62ovlz.css';
import '../../css/j/jwn4f8bbo.css';
import '../../css/n/nnjt6sbyf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="poo62ovlz"/><path class="jwn4f8bbo"/><path class="nnjt6sbyf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:rocket" {...props}></Icon>
