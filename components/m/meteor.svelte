<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrj6p8qat.css';
import '../../css/u/u75rk3mdx.css';
import '../../css/b/bkuyfq66o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><circle class="u75rk3mdx"/><path class="bkuyfq66o"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="meteor-icons:meteor" {...props}></Icon>
