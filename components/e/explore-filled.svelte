<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kerkpac7s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kerkpac7s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:explore-filled" {...props}></Icon>
