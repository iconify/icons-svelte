<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u9vdnhbpk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="u9vdnhbpk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:end-call-rounded-outline" {...props}></Icon>
