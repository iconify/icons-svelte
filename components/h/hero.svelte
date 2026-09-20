<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oc-o5ilbk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="oc-o5ilbk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:hero" {...props}></Icon>
