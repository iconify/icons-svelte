<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kbv6d6uqd.css';
import '../../css/u/u27wnzbvk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kbv6d6uqd"/><path class="u27wnzbvk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:hi-hat-24" {...props}></Icon>
