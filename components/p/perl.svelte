<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kn0uyxwmu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kn0uyxwmu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:perl" {...props}></Icon>
