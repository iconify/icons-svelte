<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s24s3go5f.css';
import '../../css/a/aba_xubdq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s24s3go5f"/><path class="aba_xubdq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:monitor-dot-filled" {...props}></Icon>
