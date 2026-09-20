<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/chowghc9o.css';
import '../../css/i/iuef7db3c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="chowghc9o"/><path class="iuef7db3c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:balance" {...props}></Icon>
