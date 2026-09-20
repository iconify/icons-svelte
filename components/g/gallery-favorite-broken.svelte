<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/q/qw59k8t0z.css';
import '../../css/l/lgbc9yk3h.css';
import '../../css/n/n57mawbaq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="qw59k8t0z"/><path class="lgbc9yk3h"/><path class="n57mawbaq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:gallery-favorite-broken" {...props}></Icon>
