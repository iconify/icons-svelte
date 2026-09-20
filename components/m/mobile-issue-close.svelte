<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pi2hptddu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="pi2hptddu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pajamas:mobile-issue-close" {...props}></Icon>
