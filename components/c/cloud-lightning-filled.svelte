<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d2k9crezi.css';
import '../../css/k/koc75zbyp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d2k9crezi"/><path class="koc75zbyp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:cloud-lightning-filled" {...props}></Icon>
