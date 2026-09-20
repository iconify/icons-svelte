<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/refi_ebwe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="refi_ebwe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:panel-bottom-open-sharp" {...props}></Icon>
