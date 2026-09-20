<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eaa4jc92m.css';
import '../../css/g/g2fn-72eb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="eaa4jc92m"/><path clip-rule="evenodd" class="g2fn-72eb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:invoice-solid" {...props}></Icon>
