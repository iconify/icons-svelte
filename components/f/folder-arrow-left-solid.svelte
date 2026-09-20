<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u2tn62lri.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="u2tn62lri"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:folder-arrow-left-solid" {...props}></Icon>
