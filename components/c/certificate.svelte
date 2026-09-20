<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrj6p8qat.css';
import '../../css/j/j8e8rbc6x.css';
import '../../css/n/nqrz7szok.css';
import '../../css/j/j6md0tpiy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="j8e8rbc6x"/><path class="nqrz7szok"/><path class="j6md0tpiy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:certificate" {...props}></Icon>
