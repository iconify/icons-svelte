<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ymglykxtj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ymglykxtj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:bag-2-outline" {...props}></Icon>
