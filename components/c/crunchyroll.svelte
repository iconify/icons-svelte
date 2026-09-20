<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kkjodbc1y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kkjodbc1y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:crunchyroll" {...props}></Icon>
