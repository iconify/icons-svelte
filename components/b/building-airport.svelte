<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrj6p8qat.css';
import '../../css/b/b8p5vjk7k.css';
import '../../css/n/n4wmd7tdc.css';
import '../../css/d/duywhdcwe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="b8p5vjk7k"/><path class="n4wmd7tdc"/><path class="duywhdcwe"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:building-airport" {...props}></Icon>
