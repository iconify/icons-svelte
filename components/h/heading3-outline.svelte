<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wtx179f9i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wtx179f9i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cuida:heading3-outline" {...props}></Icon>
