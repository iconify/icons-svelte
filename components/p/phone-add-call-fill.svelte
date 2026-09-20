<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ypft5mbdm.css';
import '../../css/v/vm4551bzs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ypft5mbdm"/><path class="vm4551bzs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:phone-add-call-fill" {...props}></Icon>
