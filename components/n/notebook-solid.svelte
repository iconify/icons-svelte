<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wxfqhybdv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wxfqhybdv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:notebook-solid" {...props}></Icon>
