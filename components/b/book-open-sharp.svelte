<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m6cjo_bkv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m6cjo_bkv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:book-open-sharp" {...props}></Icon>
