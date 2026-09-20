<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kajitxbhk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kajitxbhk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:news-fill" {...props}></Icon>
