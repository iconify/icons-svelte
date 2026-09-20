<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s52zm8mgc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s52zm8mgc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:bone" {...props}></Icon>
