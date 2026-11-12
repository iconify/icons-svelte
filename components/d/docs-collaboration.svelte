<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r_8s107tv.css';
import '../../css/e/e8df_acjv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="r_8s107tv"/><path class="e8df_acjv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:docs-collaboration" {...props}></Icon>
