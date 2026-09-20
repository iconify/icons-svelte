<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/adqk91n-z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="adqk91n-z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:history-filled" {...props}></Icon>
