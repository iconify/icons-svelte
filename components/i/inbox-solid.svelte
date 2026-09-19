<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/abat7y6yz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="abat7y6yz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:inbox-solid" {...props}></Icon>
