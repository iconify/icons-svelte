<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n3e5i7vvy.css';
import '../../css/e/esqxa_cse.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="n3e5i7vvy"/><path class="esqxa_cse"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="medical-icon:immunizations" {...props}></Icon>
