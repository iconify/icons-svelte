<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrj6p8qat.css';
import '../../css/u/u3jzqgkfd.css';
import '../../css/a/ares4u2vu.css';
import '../../css/h/ht5kii6hd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="u3jzqgkfd"/><rect class="ares4u2vu"/><rect class="ht5kii6hd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:cpu" {...props}></Icon>
