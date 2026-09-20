<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lqvm_7opk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lqvm_7opk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:folder-share" {...props}></Icon>
