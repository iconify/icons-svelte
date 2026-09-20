<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sodr2bcij.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="sodr2bcij"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:inbox-archive-filled" {...props}></Icon>
