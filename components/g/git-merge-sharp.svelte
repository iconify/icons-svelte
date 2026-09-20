<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z69fb4bck.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z69fb4bck"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:git-merge-sharp" {...props}></Icon>
