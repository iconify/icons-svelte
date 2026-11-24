<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ohm245beh.css';
import '../../css/e/edfoyo7yi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ohm245beh"/><path clip-rule="evenodd" class="edfoyo7yi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:database-search-filled" {...props}></Icon>
