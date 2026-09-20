<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iaoao3b8z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="iaoao3b8z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:football-light" {...props}></Icon>
