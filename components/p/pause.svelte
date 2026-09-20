<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrj6p8qat.css';
import '../../css/q/qgqv1ufxo.css';
import '../../css/s/sjdg-k99j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="icon-tabler nrj6p8qat"><rect class="qgqv1ufxo"/><rect class="sjdg-k99j"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:pause" {...props}></Icon>
