<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/amp1qmb0a.css';
import '../../css/s/sgi4nb-bk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="amp1qmb0a"/><path class="sgi4nb-bk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:nicotine-plus" {...props}></Icon>
