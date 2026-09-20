<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o13tqh8vy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o13tqh8vy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:book-2-fill" {...props}></Icon>
