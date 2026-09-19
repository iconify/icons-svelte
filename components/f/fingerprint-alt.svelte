<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vele90bdx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vele90bdx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:fingerprint-alt" {...props}></Icon>
