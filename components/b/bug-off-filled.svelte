<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xljqcd5eb.css';
import '../../css/i/iv92ody-l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xljqcd5eb"/><path class="iv92ody-l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:bug-off-filled" {...props}></Icon>
