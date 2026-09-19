<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ansqsn_cf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ansqsn_cf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gridicons:chevron-right" {...props}></Icon>
