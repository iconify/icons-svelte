<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrj6p8qat.css';
import '../../css/i/ie1i99bwi.css';
import '../../css/b/bxuamrbpm.css';
import '../../css/o/o8rmgetue.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ie1i99bwi"/><path class="bxuamrbpm"/><circle class="o8rmgetue"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:file-badge" {...props}></Icon>
