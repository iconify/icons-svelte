<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/al6rhabjv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="al6rhabjv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:blood-bag-donation-solid" {...props}></Icon>
