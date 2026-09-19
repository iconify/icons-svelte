<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/md4_kyv7l.css';
import '../../css/o/oa3mdsoup.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="duoicon-secondary-layer md4_kyv7l"/><path class="duoicon-primary-layer oa3mdsoup"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="duo-icons:message-3" {...props}></Icon>
