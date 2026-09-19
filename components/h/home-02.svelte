<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pkzwowb5b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pkzwowb5b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:home-02" {...props}></Icon>
