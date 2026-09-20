<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vyxb2y9tx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vyxb2y9tx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:op" {...props}></Icon>
