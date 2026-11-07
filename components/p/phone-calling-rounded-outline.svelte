<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/de4w5bjhn.css';
import '../../css/h/h6vym3bzz.css';
import '../../css/s/s_j32c9mx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="de4w5bjhn"/><path clip-rule="evenodd" class="h6vym3bzz"/><path clip-rule="evenodd" class="s_j32c9mx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:phone-calling-rounded-outline" {...props}></Icon>
