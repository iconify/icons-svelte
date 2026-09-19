<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ymwnz6xdw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ymwnz6xdw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:coffee-04" {...props}></Icon>
