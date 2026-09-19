<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n2oc1ljfc.css';
import '../../css/o/olpmu-5dh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n2oc1ljfc"/><path class="olpmu-5dh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bitcoin-icons:link-filled" {...props}></Icon>
