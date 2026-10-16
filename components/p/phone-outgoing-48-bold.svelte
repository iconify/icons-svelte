<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b5idgqqvy.css';
import '../../css/b/b2ubuucrp.css';
import '../../css/q/qfey2lb7e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="b5idgqqvy"/><path class="b2ubuucrp"/><path class="qfey2lb7e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:phone-outgoing-48-bold" {...props}></Icon>
