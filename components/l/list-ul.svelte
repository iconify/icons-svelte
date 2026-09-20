<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/daui_jbia.css';
import '../../css/f/f7gi_3bba.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="daui_jbia"/><path class="f7gi_3bba"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:list-ul" {...props}></Icon>
