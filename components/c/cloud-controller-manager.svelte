<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xgzn1hbsd.css';
import '../../css/z/z8y_nwpda.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xgzn1hbsd"/><path class="z8y_nwpda"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eos-icons:cloud-controller-manager" {...props}></Icon>
