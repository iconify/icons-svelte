<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrj6p8qat.css';
import '../../css/s/s091mgb0k.css';
import '../../css/c/cbpc6zbgf.css';
import '../../css/m/m5eds2f1v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="s091mgb0k"/><circle class="cbpc6zbgf"/><circle class="m5eds2f1v"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="meteor-icons:discord" {...props}></Icon>
