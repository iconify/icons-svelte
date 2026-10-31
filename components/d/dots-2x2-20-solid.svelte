<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yjnc-d4pe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="yjnc-d4pe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:dots-2x2-20-solid" {...props}></Icon>
