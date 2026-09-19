<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zrooq11ts.css';
import '../../css/a/apkzo_3wp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zrooq11ts"/><path class="apkzo_3wp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:image-sparkle-filled" {...props}></Icon>
