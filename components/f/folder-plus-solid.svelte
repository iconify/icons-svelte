<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c_-x8vqlk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="c_-x8vqlk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:folder-plus-solid" {...props}></Icon>
