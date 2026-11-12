<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mq9emnlot.css';
import '../../css/k/k70m9f-yz.css';
import '../../css/m/m4ht6ksod.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="mq9emnlot"/><path class="k70m9f-yz"/><path class="m4ht6ksod"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:ksuite-kchat-light" {...props}></Icon>
