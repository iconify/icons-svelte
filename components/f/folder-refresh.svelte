<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/us0mlcc8v.css';
import '../../css/m/mb6i43i-k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="us0mlcc8v"/><path class="mb6i43i-k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:folder-refresh" {...props}></Icon>
