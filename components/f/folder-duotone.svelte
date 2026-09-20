<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bmytx2b1a.css';
import '../../css/u/us0mlcc8v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bmytx2b1a"/><path clip-rule="evenodd" class="us0mlcc8v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:folder-duotone" {...props}></Icon>
