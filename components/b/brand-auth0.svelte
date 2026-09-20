<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrj6p8qat.css';
import '../../css/r/rvz5irb5y.css';
import '../../css/x/x51oakbtg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="rvz5irb5y"/><path class="x51oakbtg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:brand-auth0" {...props}></Icon>
