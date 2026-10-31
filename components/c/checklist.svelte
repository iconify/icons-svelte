<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lsolh_5rf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lsolh_5rf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:checklist" {...props}></Icon>
