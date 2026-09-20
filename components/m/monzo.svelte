<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/st3sq4bcz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="st3sq4bcz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:monzo" {...props}></Icon>
