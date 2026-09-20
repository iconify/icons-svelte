<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nuc5lzbdd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nuc5lzbdd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:emoji-wink-solid" {...props}></Icon>
