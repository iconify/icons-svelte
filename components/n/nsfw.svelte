<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lkxm5ccrh.css';
import '../../css/v/vsj2klbek.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lkxm5ccrh"/><path class="vsj2klbek"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:nsfw" {...props}></Icon>
