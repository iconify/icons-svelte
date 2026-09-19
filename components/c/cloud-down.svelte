<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/z/zpvs2hbkd.css';
import '../../css/p/py7ktqbvf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#ciCloudDown0)"><path class="zpvs2hbkd"/></g><defs><clipPath id="ciCloudDown0"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:cloud-down" {...props}></Icon>
