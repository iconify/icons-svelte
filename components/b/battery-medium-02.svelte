<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zwz2ijbhp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zwz2ijbhp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:battery-medium-02" {...props}></Icon>
