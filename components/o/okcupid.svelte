<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dytoz5beu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dytoz5beu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:okcupid" {...props}></Icon>
