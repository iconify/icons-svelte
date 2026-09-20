<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/noh39bbir.css';
import '../../css/x/xxvlnybzz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="noh39bbir"/><path class="xxvlnybzz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:battery-2-solid" {...props}></Icon>
