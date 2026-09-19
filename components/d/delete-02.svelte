<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b3k7hac6w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b3k7hac6w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:delete-02" {...props}></Icon>
