<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y3sdo1bpk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y3sdo1bpk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:credit-card-accept" {...props}></Icon>
