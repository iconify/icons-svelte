<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aafltn7qk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="aafltn7qk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:notes" {...props}></Icon>
