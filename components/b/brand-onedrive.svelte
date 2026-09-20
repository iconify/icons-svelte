<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sjw8acbwk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sjw8acbwk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:brand-onedrive" {...props}></Icon>
