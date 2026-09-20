<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/scc60hb6k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="scc60hb6k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:folder-x-sharp" {...props}></Icon>
