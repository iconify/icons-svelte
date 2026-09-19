<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uf7u_csrv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uf7u_csrv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:npo" {...props}></Icon>
