<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bbmlbccky.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bbmlbccky"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:logout-02" {...props}></Icon>
