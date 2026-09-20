<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kjc9o4b-j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kjc9o4b-j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:folder-arrow-up-solid" {...props}></Icon>
