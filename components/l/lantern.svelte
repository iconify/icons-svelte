<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/opfvhq6uh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="opfvhq6uh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:lantern" {...props}></Icon>
