<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a24b_-4jq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="a24b_-4jq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:folder-alt-light" {...props}></Icon>
