<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrj6p8qat.css';
import '../../css/a/ajbswkpvd.css';
import '../../css/b/b4fcxnb0b.css';
import '../../css/n/nol19vq4t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ajbswkpvd"/><path class="b4fcxnb0b"/><circle class="nol19vq4t"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:image-plus" {...props}></Icon>
