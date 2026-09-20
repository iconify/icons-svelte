<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n3t6plt2w.css';
import '../../css/y/yddqsqbhk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="n3t6plt2w"/><path clip-rule="evenodd" class="yddqsqbhk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:message-no-access-solid" {...props}></Icon>
