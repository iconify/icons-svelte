<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/smxvd6p6i.css';
import '../../css/p/pe_k9tbko.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="smxvd6p6i"/><path class="pe_k9tbko"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:launch" {...props}></Icon>
