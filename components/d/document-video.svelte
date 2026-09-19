<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ed7ytxbww.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ed7ytxbww"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:document-video" {...props}></Icon>
