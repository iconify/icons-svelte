<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wdzqpv1gd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wdzqpv1gd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:bill-check-filled" {...props}></Icon>
