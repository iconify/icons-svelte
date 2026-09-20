<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bf22_73oq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bf22_73oq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:at-symbol-light" {...props}></Icon>
