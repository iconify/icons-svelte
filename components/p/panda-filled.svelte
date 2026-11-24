<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uvamfzb5a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="uvamfzb5a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:panda-filled" {...props}></Icon>
