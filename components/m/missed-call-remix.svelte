<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kmu6xkaaq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="kmu6xkaaq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:missed-call-remix" {...props}></Icon>
