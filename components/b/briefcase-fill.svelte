<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kqwj-dbhq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kqwj-dbhq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:briefcase-fill" {...props}></Icon>
