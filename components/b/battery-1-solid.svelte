<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qyxmmfrwe.css';
import '../../css/x/xxvlnybzz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="qyxmmfrwe"/><path class="xxvlnybzz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:battery-1-solid" {...props}></Icon>
