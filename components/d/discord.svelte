<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b9t5tfwvk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b9t5tfwvk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:discord" {...props}></Icon>
