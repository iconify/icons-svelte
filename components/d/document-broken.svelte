<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/h/h4m9tpedx.css';
import '../../css/g/g100mfbew.css';
import '../../css/h/hg-jr4bbd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="h4m9tpedx"/><path class="g100mfbew"/><path class="hg-jr4bbd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:document-broken" {...props}></Icon>
