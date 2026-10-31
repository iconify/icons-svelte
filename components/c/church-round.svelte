<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kc75hcczw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kc75hcczw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:church-round" {...props}></Icon>
