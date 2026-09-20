<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/igs6o1bpq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="igs6o1bpq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:gsap" {...props}></Icon>
