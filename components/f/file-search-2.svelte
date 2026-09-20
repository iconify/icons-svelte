<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrj6p8qat.css';
import '../../css/d/d-nkafbhy.css';
import '../../css/g/g6wanyb_h.css';
import '../../css/p/pzb87xb0u.css';
import '../../css/k/ka48d2b9k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="d-nkafbhy"/><path class="g6wanyb_h"/><circle class="pzb87xb0u"/><path class="ka48d2b9k"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:file-search-2" {...props}></Icon>
