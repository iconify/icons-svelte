<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wv-d25bbn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wv-d25bbn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:cloud-x-sharp-fill" {...props}></Icon>
