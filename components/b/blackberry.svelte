<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s271kzbcl.css';
import '../../css/c/cw8eslg_b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s271kzbcl"/><path class="cw8eslg_b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uim:blackberry" {...props}></Icon>
