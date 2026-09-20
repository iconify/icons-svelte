<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c47vucc6q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c47vucc6q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:raylib" {...props}></Icon>
