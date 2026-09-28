<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mjx9skd3v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mjx9skd3v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:hypit" {...props}></Icon>
