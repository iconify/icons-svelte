<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rak8y7bfa.css';
import '../../css/o/o3-o5nogz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="rak8y7bfa"/><path class="o3-o5nogz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:account-logout" {...props}></Icon>
