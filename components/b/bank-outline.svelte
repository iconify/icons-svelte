<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/to-5kdesz.css';
import '../../css/b/buf9gg7ha.css';
import '../../css/s/sh_se6b_t.css';
import '../../css/c/ch5we-bio.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="to-5kdesz"><path class="buf9gg7ha"/><path class="sh_se6b_t"/><path class="ch5we-bio"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bitcoin-icons:bank-outline" {...props}></Icon>
