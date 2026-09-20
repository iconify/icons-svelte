<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rnacsvbpp.css';
import '../../css/t/t-rbbb6gw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rnacsvbpp"/><path clip-rule="evenodd" class="t-rbbb6gw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:ai-chat-fill" {...props}></Icon>
