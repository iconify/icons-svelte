<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d2kvgvbvc.css';
import '../../css/k/kzytk1b6j.css';
import '../../css/f/fdhkvebrt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="d2kvgvbvc"><path class="kzytk1b6j"/><path class="fdhkvebrt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gcp:key-management-service" {...props}></Icon>
