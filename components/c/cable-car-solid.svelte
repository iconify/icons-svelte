<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qr4bq9bcb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qr4bq9bcb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:cable-car-solid" {...props}></Icon>
